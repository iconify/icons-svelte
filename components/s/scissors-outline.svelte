<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqe620tbb.css';
import '../../css/n/nxaii_ued.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mqe620tbb"/><path class="nxaii_ued"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:scissors-outline" {...props}></Icon>
