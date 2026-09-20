<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilao8nohd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilao8nohd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sonatype" {...props}></Icon>
