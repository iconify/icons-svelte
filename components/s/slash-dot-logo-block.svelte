<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmf-2wqcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tmf-2wqcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:slash-dot-logo-block" {...props}></Icon>
