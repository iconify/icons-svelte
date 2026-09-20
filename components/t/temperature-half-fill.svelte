<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay8cjh3ds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ay8cjh3ds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:temperature-half-fill" {...props}></Icon>
