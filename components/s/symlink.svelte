<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvfz8lcts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pvfz8lcts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:symlink" {...props}></Icon>
