<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nskmalzgz.css';
import '../../css/v/v97u7ccna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nskmalzgz"/><path class="v97u7ccna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:side-nav-collapse" {...props}></Icon>
