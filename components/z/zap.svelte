<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh-17nb3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jh-17nb3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:zap" {...props}></Icon>
