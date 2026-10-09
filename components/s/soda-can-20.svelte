<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g113u0-1c.css';
import '../../css/m/m8xzmqmih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g113u0-1c"/><path class="m8xzmqmih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:soda-can-20" {...props}></Icon>
