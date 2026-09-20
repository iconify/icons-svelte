<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfbx6odob.css';
import '../../css/r/r7sd-ibvw.css';
import '../../css/h/hrqt4gbvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="jfbx6odob"/><circle class="r7sd-ibvw"/><path class="hrqt4gbvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:thermometer" {...props}></Icon>
