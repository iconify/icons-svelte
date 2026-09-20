<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ka0k06blu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ka0k06blu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:speaker-multiple" {...props}></Icon>
