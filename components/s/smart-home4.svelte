<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9tvt8oor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o9tvt8oor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:smart-home4" {...props}></Icon>
