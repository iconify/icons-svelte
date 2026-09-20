<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3s8zzbno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="p3s8zzbno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:school-outline" {...props}></Icon>
