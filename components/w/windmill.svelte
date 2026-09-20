<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cahlgsbxb.css';
import '../../css/f/f32tc6mne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cahlgsbxb"/><path class="f32tc6mne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:windmill" {...props}></Icon>
