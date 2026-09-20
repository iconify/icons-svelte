<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o19vw7hlu.css';
import '../../css/a/a2s72obzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o19vw7hlu"/><path clip-rule="evenodd" class="a2s72obzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:undeploy" {...props}></Icon>
