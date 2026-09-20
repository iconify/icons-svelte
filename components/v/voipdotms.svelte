<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phxj0ib3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="phxj0ib3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:voipdotms" {...props}></Icon>
