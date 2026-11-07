<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdsgiib1a.css';
import '../../css/g/gmzuw1e_j.css';
import '../../css/c/cha8n8h4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sdsgiib1a"/><path class="gmzuw1e_j"/><path class="cha8n8h4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:suitcase-outline" {...props}></Icon>
