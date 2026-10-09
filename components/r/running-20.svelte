<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qokocnbbw.css';
import '../../css/v/v9e56nbyl.css';
import '../../css/e/eswagv34a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qokocnbbw"/><path class="v9e56nbyl"/><path class="eswagv34a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:running-20" {...props}></Icon>
