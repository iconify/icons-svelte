<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujvs38b6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ujvs38b6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:tooltip" {...props}></Icon>
