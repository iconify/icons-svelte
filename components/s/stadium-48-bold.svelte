<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf4iecijn.css';
import '../../css/y/ylwrz8bdu.css';
import '../../css/a/a9vul7b8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pf4iecijn"/><path class="ylwrz8bdu"/><path class="a9vul7b8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:stadium-48-bold" {...props}></Icon>
