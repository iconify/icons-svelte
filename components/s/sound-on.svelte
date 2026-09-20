<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbwm7p47f.css';
import '../../css/o/olyf9ubyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sbwm7p47f"/><path class="olyf9ubyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:sound-on" {...props}></Icon>
