<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd19m6j6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jd19m6j6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:snow" {...props}></Icon>
