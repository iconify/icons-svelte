<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6nq6mb0m.css';
import '../../css/l/l73m9po7l.css';
import '../../css/y/ybe6y-5ox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="k6nq6mb0m"/><path class="l73m9po7l"/><path class="ybe6y-5ox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:systemd-wordmark" {...props}></Icon>
