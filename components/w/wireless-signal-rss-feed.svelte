<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/y/y46gdktui.css';
import '../../css/r/rqlsr2bvh.css';
import '../../css/f/fc2zsxbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="y46gdktui"/><path class="rqlsr2bvh"/><path class="fc2zsxbxd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:wireless-signal-rss-feed" {...props}></Icon>
