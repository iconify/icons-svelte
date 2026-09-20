<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kywahdcjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kywahdcjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:sonarqube-server" {...props}></Icon>
