<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgso-g05s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pgso-g05s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:wechat" {...props}></Icon>
