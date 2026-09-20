<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz_34wb2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iz_34wb2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:youtube" {...props}></Icon>
