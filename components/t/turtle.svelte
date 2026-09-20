<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqwiuu6zw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eqwiuu6zw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:turtle" {...props}></Icon>
