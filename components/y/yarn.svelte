<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfglxw37l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qfglxw37l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:yarn" {...props}></Icon>
