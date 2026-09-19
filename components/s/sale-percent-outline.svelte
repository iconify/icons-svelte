<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qihv1wb4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qihv1wb4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:sale-percent-outline" {...props}></Icon>
