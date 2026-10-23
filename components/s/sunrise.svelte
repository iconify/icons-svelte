<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu9cchatv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mu9cchatv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:sunrise" {...props}></Icon>
