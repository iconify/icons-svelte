<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/y/y6f0jibvm.css';
import '../../css/c/cbdkjzbyk.css';
import '../../css/b/b-7asgbpr.css';
import '../../css/p/pmtqnwzqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="y6f0jibvm"/><path class="cbdkjzbyk"/><path class="b-7asgbpr"/><path class="pmtqnwzqn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:volkswagen" {...props}></Icon>
