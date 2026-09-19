<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apnd5pbku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="apnd5pbku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:t-rex-filled" {...props}></Icon>
