<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcs0clwsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qcs0clwsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:sliders-vertical-sharp-fill" {...props}></Icon>
