<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe8gjco0e.css';
import '../../css/d/d241niblj.css';
import '../../css/k/kltxv0ssh.css';
import '../../css/k/kdz4acc8r.css';
import '../../css/j/ja_tpciet.css';
import '../../css/t/txec4eymi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="xe8gjco0e"/><circle class="d241niblj"/><path class="kltxv0ssh"/><g class="kdz4acc8r"><circle class="ja_tpciet"/><path class="txec4eymi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:white-chess-king" {...props}></Icon>
