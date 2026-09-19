<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf2zwlsuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="nf2zwlsuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:white-left-backhand-index" {...props}></Icon>
