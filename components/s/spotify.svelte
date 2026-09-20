<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ge7sm6btc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ge7sm6btc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:spotify" {...props}></Icon>
