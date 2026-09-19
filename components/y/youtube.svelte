<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to-5kdesz.css';
import '../../css/d/dblasrb2v.css';
import '../../css/w/wxc7mbbhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="to-5kdesz"><path class="dblasrb2v"/><path class="wxc7mbbhr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:youtube" {...props}></Icon>
