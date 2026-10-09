<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlfpc8feq.css';
import '../../css/s/sew1b1r7k.css';
import '../../css/c/c65-ehvfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jlfpc8feq"/><path class="sew1b1r7k"/><path class="c65-ehvfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wildfire-48" {...props}></Icon>
