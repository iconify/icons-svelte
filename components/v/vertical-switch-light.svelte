<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv5fhxp1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pv5fhxp1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:vertical-switch-light" {...props}></Icon>
