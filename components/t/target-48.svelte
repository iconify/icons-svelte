<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hac57wbhi.css';
import '../../css/i/i2a3t5bgb.css';
import '../../css/i/i5i-ymejz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hac57wbhi"/><path class="i2a3t5bgb"/><path class="i5i-ymejz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:target-48" {...props}></Icon>
