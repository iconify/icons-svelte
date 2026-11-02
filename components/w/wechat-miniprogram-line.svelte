<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5qow_bib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q5qow_bib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wechat-miniprogram-line" {...props}></Icon>
