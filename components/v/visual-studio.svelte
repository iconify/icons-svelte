<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xra_zg-lm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xra_zg-lm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:visual-studio" {...props}></Icon>
