<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/moc26lgsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="moc26lgsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:waveform-path-badge-minus" {...props}></Icon>
