<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr__c4rcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pr__c4rcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spikes-full" {...props}></Icon>
