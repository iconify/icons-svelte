<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1gacebmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q1gacebmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:vmware-engine" {...props}></Icon>
