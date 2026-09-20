<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ziao2px2e.css';
import '../../css/h/hyv-2gbfp.css';
import '../../css/k/k9mgxccva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ziao2px2e"/><path class="hyv-2gbfp"/><path class="k9mgxccva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:taskfile" {...props}></Icon>
