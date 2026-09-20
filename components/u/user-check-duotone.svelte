<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow15xdb1e.css';
import '../../css/e/eeg6scbqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ow15xdb1e"/><path class="eeg6scbqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:user-check-duotone" {...props}></Icon>
