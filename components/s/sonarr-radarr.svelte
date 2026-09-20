<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-wkamaxf.css';
import '../../css/v/v9pw7wbff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a-wkamaxf"/><path class="v9pw7wbff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sonarr-radarr" {...props}></Icon>
