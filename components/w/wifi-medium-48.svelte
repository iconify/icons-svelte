<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddstmrebw.css';
import '../../css/x/xjh2b-bdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ddstmrebw"/><path class="xjh2b-bdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wifi-medium-48" {...props}></Icon>
