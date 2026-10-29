<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thj3mqbqh.css';
import '../../css/u/uqi_583re.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thj3mqbqh wm-k"/><path class="uqi_583re wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:subscript" {...props}></Icon>
