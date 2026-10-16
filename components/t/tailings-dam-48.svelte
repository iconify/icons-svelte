<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjbhs-95h.css';
import '../../css/z/zns5-suvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tjbhs-95h"/><path class="zns5-suvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tailings-dam-48" {...props}></Icon>
