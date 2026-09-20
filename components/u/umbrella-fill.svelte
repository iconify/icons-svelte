<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrg5sccwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hrg5sccwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:umbrella-fill" {...props}></Icon>
