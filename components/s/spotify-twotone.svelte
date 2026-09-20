<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzcwhu.css';
import '../../css/l/l13gug.css';
import '../../css/w/w5j5uc.css';
import '../../css/y/y4wbml.css';
import '../../css/n/nv-v8y.css';
import '../../css/t/tokjwc.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-66.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hzcwhu l13gug"/><path class="hzcwhu w5j5uc y4wbml"/><path class="hzcwhu nv-v8y y4wbml"/><path class="hzcwhu tokjwc y4wbml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:spotify-twotone" {...props}></Icon>
