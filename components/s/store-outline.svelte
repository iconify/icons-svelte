<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do-02ka4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="do-02ka4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:store-outline" {...props}></Icon>
