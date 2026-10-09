<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac7p6yblo.css';
import '../../css/n/njy6bmz6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ac7p6yblo"/><path class="njy6bmz6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wattmeter-48" {...props}></Icon>
