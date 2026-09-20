<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g28vpdbis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g28vpdbis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:store-2-fill" {...props}></Icon>
