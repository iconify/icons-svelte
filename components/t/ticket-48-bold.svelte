<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-7-2mbbf.css';
import '../../css/o/o76p7lbzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u-7-2mbbf"/><path class="o76p7lbzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ticket-48-bold" {...props}></Icon>
