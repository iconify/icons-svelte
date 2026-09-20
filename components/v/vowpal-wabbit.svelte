<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnf5szb2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mnf5szb2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:vowpal-wabbit" {...props}></Icon>
