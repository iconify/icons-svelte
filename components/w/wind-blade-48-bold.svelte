<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac35u9zca.css';
import '../../css/n/n828jkbji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ac35u9zca"/><path class="n828jkbji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wind-blade-48-bold" {...props}></Icon>
