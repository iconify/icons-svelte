<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxp7sbciw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lxp7sbciw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:seedling-solid" {...props}></Icon>
