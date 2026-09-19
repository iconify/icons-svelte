<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5kv900nb.css';
import '../../css/v/vgev59bwn.css';
import '../../css/y/yso2edb_p.css';
import '../../css/z/ziil8acyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q5kv900nb"/><g class="vgev59bwn"><path transform="matrix(.13927 0 0 .13933 -.413 .02)" class="yso2edb_p"/><path transform="matrix(.13927 0 0 .13933 -.413 .02)" class="ziil8acyu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:yarn-lock" {...props}></Icon>
