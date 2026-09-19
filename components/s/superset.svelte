<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyfp4wbwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jyfp4wbwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:superset" {...props}></Icon>
