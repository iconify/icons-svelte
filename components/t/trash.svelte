<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsyjwjddq.css';
import '../../css/c/ctr08lbas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="rsyjwjddq"/><path class="ctr08lbas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:trash" {...props}></Icon>
