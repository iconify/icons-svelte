<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1gq8obfz.css';
import '../../css/v/vil7ki9ez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m1gq8obfz"/><path class="vil7ki9ez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wallet-48-bold" {...props}></Icon>
