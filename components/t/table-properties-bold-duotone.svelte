<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nayqy1c_r.css';
import '../../css/m/mjlzetbue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nayqy1c_r"/><path class="mjlzetbue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:table-properties-bold-duotone" {...props}></Icon>
