<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n82zcy6-h.css';
import '../../css/c/clhe_ezsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n82zcy6-h"/><path class="clhe_ezsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:search" {...props}></Icon>
