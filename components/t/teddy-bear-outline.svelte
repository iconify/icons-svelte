<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtdzw85ub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qtdzw85ub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:teddy-bear-outline" {...props}></Icon>
