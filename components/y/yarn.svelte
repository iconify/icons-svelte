<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqplhccxe.css';
import '../../css/m/m597sacji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":518,"height":518};
const content = `<path class="kqplhccxe"/><path class="m597sacji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:yarn" {...props}></Icon>
