<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qut9t6lxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qut9t6lxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:teamviewer" {...props}></Icon>
