<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vevl8ac-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vevl8ac-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-factorial-fill" {...props}></Icon>
