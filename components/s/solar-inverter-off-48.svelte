<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zerildbqi.css';
import '../../css/k/kziqmybgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zerildbqi"/><path class="kziqmybgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-inverter-off-48" {...props}></Icon>
