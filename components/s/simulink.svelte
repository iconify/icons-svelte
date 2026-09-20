<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz-uhfsal.css';
import '../../css/h/hn2o_abjx.css';
import '../../css/w/wdbpibcck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":4.233,"height":4.233};
const content = `<path class="pz-uhfsal"/><path class="hn2o_abjx"/><path class="wdbpibcck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:simulink" {...props}></Icon>
