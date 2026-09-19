<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7ftu38ng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="j7ftu38ng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:vkontakte" {...props}></Icon>
