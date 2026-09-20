<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcx7xcdvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hcx7xcdvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:walking-1" {...props}></Icon>
