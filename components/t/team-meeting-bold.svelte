<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osdr6bbou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="osdr6bbou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:team-meeting-bold" {...props}></Icon>
