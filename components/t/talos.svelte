<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b20yb556g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b20yb556g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:talos" {...props}></Icon>
