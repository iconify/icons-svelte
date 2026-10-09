<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhq8k4w1w.css';
import '../../css/o/ojgsrdbfo.css';
import '../../css/m/mibj8nzcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rhq8k4w1w"/><path class="ojgsrdbfo"/><path class="mibj8nzcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:stadium-20" {...props}></Icon>
