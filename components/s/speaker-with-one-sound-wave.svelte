<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwlm6_lai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="zwlm6_lai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:speaker-with-one-sound-wave" {...props}></Icon>
