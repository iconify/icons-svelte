<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjin6hi9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sjin6hi9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sonarqube-server" {...props}></Icon>
