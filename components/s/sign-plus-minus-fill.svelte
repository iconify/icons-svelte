<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nca5e5b3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nca5e5b3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-plus-minus-fill" {...props}></Icon>
