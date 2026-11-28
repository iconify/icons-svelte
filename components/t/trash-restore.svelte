<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/na4rgbmvw.css';
import '../../css/v/vpkn_nb1r.css';
import '../../css/f/f9guiachc.css';
import '../../css/u/ustj7ibxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="na4rgbmvw"/><path class="vpkn_nb1r"/><path class="f9guiachc"/><path class="ustj7ibxg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:trash-restore" {...props}></Icon>
