<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf80y80vm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mf80y80vm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:text-align-center" {...props}></Icon>
