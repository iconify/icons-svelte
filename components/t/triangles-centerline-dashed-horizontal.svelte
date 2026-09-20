<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ak-_2kb0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ak-_2kb0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:triangles-centerline-dashed-horizontal" {...props}></Icon>
