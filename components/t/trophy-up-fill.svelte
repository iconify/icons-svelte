<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmf4p5-5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmf4p5-5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:trophy-up-fill" {...props}></Icon>
