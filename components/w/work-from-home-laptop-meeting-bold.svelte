<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uoga5ubay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uoga5ubay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:work-from-home-laptop-meeting-bold" {...props}></Icon>
