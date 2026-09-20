<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qiauddejf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qiauddejf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:zoom-logo-1" {...props}></Icon>
