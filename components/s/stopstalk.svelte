<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7kpuwdxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o7kpuwdxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:stopstalk" {...props}></Icon>
