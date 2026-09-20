<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akgok5bfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="akgok5bfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:wiken" {...props}></Icon>
