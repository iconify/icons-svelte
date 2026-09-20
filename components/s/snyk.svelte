<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-6jdu-cd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-6jdu-cd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:snyk" {...props}></Icon>
