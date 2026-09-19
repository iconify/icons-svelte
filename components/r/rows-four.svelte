<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avqaorbxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avqaorbxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:rows-four" {...props}></Icon>
