<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnb8lgb3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bnb8lgb3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:user-circle-outline" {...props}></Icon>
