<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmyxs9_0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nmyxs9_0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:volume-min" {...props}></Icon>
