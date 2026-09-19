<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yi3op5bxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yi3op5bxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:youtube" {...props}></Icon>
