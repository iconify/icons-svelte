<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnh4tjnml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="qnh4tjnml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:user-shield" {...props}></Icon>
