<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytgae-raz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ytgae-raz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-minus-square-fill" {...props}></Icon>
