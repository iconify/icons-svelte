<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9m4xgb3u.css';
import '../../css/f/fbt2ffbmg.css';
import '../../css/r/roslnzb2d.css';
import '../../css/g/gh10ve00x.css';
import '../../css/h/h4j_a1xza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="h9m4xgb3u"/><path class="fbt2ffbmg"/><path class="roslnzb2d"/><path class="gh10ve00x"/><path class="h4j_a1xza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:western-sahara" {...props}></Icon>
