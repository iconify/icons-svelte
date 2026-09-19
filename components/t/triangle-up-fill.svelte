<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do2484mdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="do2484mdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:triangle-up-fill" {...props}></Icon>
