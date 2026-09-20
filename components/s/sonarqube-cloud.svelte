<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enih07b1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="enih07b1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sonarqube-cloud" {...props}></Icon>
