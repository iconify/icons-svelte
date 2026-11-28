<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx7r33b-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xx7r33b-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:user-circle-minus" {...props}></Icon>
