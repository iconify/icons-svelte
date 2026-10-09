<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6k8gux7d.css';
import '../../css/i/ilc61dbwx.css';
import '../../css/q/qdwklz3cm.css';
import '../../css/y/yhk6owtet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h6k8gux7d"/><path class="ilc61dbwx"/><path class="qdwklz3cm"/><path class="yhk6owtet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wake-effect-20-bold" {...props}></Icon>
