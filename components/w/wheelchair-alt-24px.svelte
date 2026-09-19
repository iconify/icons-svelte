<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwn7tqbgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwn7tqbgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:wheelchair-alt-24px" {...props}></Icon>
