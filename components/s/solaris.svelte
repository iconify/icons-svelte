<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b__w9xbtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b__w9xbtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:solaris" {...props}></Icon>
