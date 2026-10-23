<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6t456b9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g6t456b9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:user-round-minus" {...props}></Icon>
