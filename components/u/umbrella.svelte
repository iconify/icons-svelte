<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt97p4afp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xt97p4afp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:umbrella" {...props}></Icon>
