<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9kli0b2o.css';
import '../../css/f/fr0jglbrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s9kli0b2o"/><path class="fr0jglbrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:storage-heater-20" {...props}></Icon>
