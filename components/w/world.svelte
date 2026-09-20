<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqax-6b-d.css';
import '../../css/n/nf9l68beg.css';
import '../../css/w/wdplfeaon.css';
import '../../css/a/a8qw23j_z.css';
import '../../css/x/x6pps9bac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="jqax-6b-d"><path class="nf9l68beg"/><path class="wdplfeaon"/><path class="a8qw23j_z"/><path class="x6pps9bac"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:world" {...props}></Icon>
