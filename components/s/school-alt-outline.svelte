<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekp4itbuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ekp4itbuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:school-alt-outline" {...props}></Icon>
