<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7v6w9b9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l7v6w9b9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:zoom-out-fill" {...props}></Icon>
