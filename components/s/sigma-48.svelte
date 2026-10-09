<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw2pwjbgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pw2pwjbgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sigma-48" {...props}></Icon>
