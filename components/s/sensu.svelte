<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4euz1bth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a4euz1bth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:sensu" {...props}></Icon>
